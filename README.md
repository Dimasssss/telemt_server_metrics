# Server Metrics 2026-03-14 11:42:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 193403.2 (53h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5590370
telemt_connections_bad_total 58421
telemt_handshake_timeouts_total 123450
telemt_upstream_connect_attempt_total 40499
telemt_upstream_connect_success_total 40241
telemt_upstream_connect_fail_total 258
telemt_upstream_connect_attempts_per_request{bucket="1"} 40499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 258
telemt_me_keepalive_timeout_total 7727
telemt_me_reconnect_attempts_total 44669
telemt_me_reconnect_success_total 28298
telemt_me_reader_eof_total 30470
telemt_me_idle_close_by_peer_total 30469
telemt_me_route_drop_no_conn_total 2115133
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5127215
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19670
telemt_desync_full_logged_total 5368
telemt_desync_suppressed_total 14302
telemt_desync_frames_bucket_total{bucket="1_2"} 4773
telemt_desync_frames_bucket_total{bucket="3_10"} 7491
telemt_desync_frames_bucket_total{bucket="gt_10"} 7406
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 29223
telemt_me_refill_failed_total 506
telemt_me_writer_restored_same_endpoint_total 28285
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 925
telemt_user_connections_total{user="hello"} 5128646
telemt_user_connections_current{user="hello"} 1739
telemt_user_octets_from_client{user="hello"} 79440152052 (73.98 GB)
telemt_user_octets_to_client{user="hello"} 1633044578241 (1.49 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 484
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 93067.3 (25h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1065269
telemt_connections_bad_total 58876
telemt_handshake_timeouts_total 24479
telemt_upstream_connect_attempt_total 24260
telemt_upstream_connect_success_total 23962
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 24260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10601
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 263
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_keepalive_timeout_total 2299
telemt_me_reconnect_attempts_total 32290
telemt_me_reconnect_success_total 17290
telemt_me_reader_eof_total 18649
telemt_me_idle_close_by_peer_total 18648
telemt_me_route_drop_no_conn_total 359193
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 875236
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2442
telemt_desync_full_logged_total 767
telemt_desync_suppressed_total 1675
telemt_desync_frames_bucket_total{bucket="1_2"} 619
telemt_desync_frames_bucket_total{bucket="3_10"} 1020
telemt_desync_frames_bucket_total{bucket="gt_10"} 803
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18004
telemt_me_refill_failed_total 462
telemt_me_writer_restored_same_endpoint_total 17282
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 714
telemt_user_connections_total{user="hello"} 877150
telemt_user_connections_current{user="hello"} 723
telemt_user_octets_from_client{user="hello"} 9565643045 (8.91 GB)
telemt_user_octets_to_client{user="hello"} 308924810560 (287.71 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 223023.9 (61h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3963219
telemt_connections_bad_total 46185
telemt_handshake_timeouts_total 266979
telemt_upstream_connect_attempt_total 50309
telemt_upstream_connect_success_total 50288
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 50309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23470
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 259
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11102
telemt_me_reconnect_attempts_total 44870
telemt_me_reconnect_success_total 38870
telemt_me_reader_eof_total 41285
telemt_me_idle_close_by_peer_total 41283
telemt_me_route_drop_no_conn_total 1361827
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3315084
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10689
telemt_desync_full_logged_total 3611
telemt_desync_suppressed_total 7078
telemt_desync_frames_bucket_total{bucket="1_2"} 1946
telemt_desync_frames_bucket_total{bucket="3_10"} 3864
telemt_desync_frames_bucket_total{bucket="gt_10"} 4879
telemt_pool_swap_total 206
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 39445
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 38829
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 575
telemt_user_connections_total{user="hello"} 3314230
telemt_user_connections_current{user="hello"} 1021
telemt_user_octets_from_client{user="hello"} 56320935300 (52.45 GB)
telemt_user_octets_to_client{user="hello"} 1187474498353 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 223026.7 (61h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2597580
telemt_connections_bad_total 23506
telemt_handshake_timeouts_total 332600
telemt_upstream_connect_attempt_total 68926
telemt_upstream_connect_success_total 66419
telemt_upstream_connect_fail_total 2370
telemt_upstream_connect_attempts_per_request{bucket="1"} 68652
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26698
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2369
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20809
telemt_me_reconnect_attempts_total 61076
telemt_me_reconnect_success_total 48297
telemt_me_reader_eof_total 51749
telemt_me_idle_close_by_peer_total 51741
telemt_me_route_drop_no_conn_total 864157
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2031975
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4105
telemt_desync_full_logged_total 1349
telemt_desync_suppressed_total 2756
telemt_desync_frames_bucket_total{bucket="1_2"} 1166
telemt_desync_frames_bucket_total{bucket="3_10"} 1676
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 191
telemt_me_writer_removed_unexpected_total 49116
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 48272
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 819
telemt_user_connections_total{user="hello"} 2038348
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 30223889103 (28.15 GB)
telemt_user_octets_to_client{user="hello"} 728429345658 (678.40 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 92460.0 (25h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1050625
telemt_connections_bad_total 18082
telemt_handshake_timeouts_total 13689
telemt_upstream_connect_attempt_total 22664
telemt_upstream_connect_success_total 22045
telemt_upstream_connect_fail_total 619
telemt_upstream_connect_attempts_per_request{bucket="1"} 22664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11445
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 619
telemt_me_keepalive_timeout_total 1747
telemt_me_reconnect_attempts_total 81133
telemt_me_reconnect_success_total 17440
telemt_me_reader_eof_total 19837
telemt_me_idle_close_by_peer_total 19836
telemt_me_route_drop_no_conn_total 425027
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 972331
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2615
telemt_desync_full_logged_total 817
telemt_desync_suppressed_total 1798
telemt_desync_frames_bucket_total{bucket="1_2"} 926
telemt_desync_frames_bucket_total{bucket="3_10"} 938
telemt_desync_frames_bucket_total{bucket="gt_10"} 751
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19588
telemt_me_refill_failed_total 1985
telemt_me_writer_restored_same_endpoint_total 17435
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2148
telemt_user_connections_total{user="hello"} 971542
telemt_user_connections_current{user="hello"} 644
telemt_user_octets_from_client{user="hello"} 17004834980 (15.84 GB)
telemt_user_octets_to_client{user="hello"} 328310232704 (305.76 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 88
```