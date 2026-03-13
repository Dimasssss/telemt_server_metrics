# Server Metrics 2026-03-13 19:35:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 135428.7 (37h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4323730
telemt_connections_bad_total 37799
telemt_handshake_timeouts_total 105542
telemt_upstream_connect_attempt_total 28406
telemt_upstream_connect_success_total 28213
telemt_upstream_connect_fail_total 193
telemt_upstream_connect_attempts_per_request{bucket="1"} 28406
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 193
telemt_me_keepalive_timeout_total 6526
telemt_me_reconnect_attempts_total 29230
telemt_me_reconnect_success_total 19114
telemt_me_reader_eof_total 20518
telemt_me_idle_close_by_peer_total 20517
telemt_me_route_drop_no_conn_total 1625334
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3954106
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15551
telemt_desync_full_logged_total 4146
telemt_desync_suppressed_total 11405
telemt_desync_frames_bucket_total{bucket="1_2"} 3869
telemt_desync_frames_bucket_total{bucket="3_10"} 5926
telemt_desync_frames_bucket_total{bucket="gt_10"} 5756
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 19704
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19101
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 590
telemt_user_connections_total{user="hello"} 3956268
telemt_user_connections_current{user="hello"} 1544
telemt_user_octets_from_client{user="hello"} 57301289176 (53.37 GB)
telemt_user_octets_to_client{user="hello"} 1245187180865 (1.13 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 397
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 35092.3 (9h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 509234
telemt_connections_bad_total 39579
telemt_handshake_timeouts_total 11109
telemt_upstream_connect_attempt_total 10259
telemt_upstream_connect_success_total 10046
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 10259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3938
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_timeout_total 1868
telemt_me_reconnect_attempts_total 9679
telemt_me_reconnect_success_total 6265
telemt_me_reader_eof_total 6621
telemt_me_idle_close_by_peer_total 6620
telemt_me_route_drop_no_conn_total 190797
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 442514
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1536
telemt_desync_full_logged_total 412
telemt_desync_suppressed_total 1124
telemt_desync_frames_bucket_total{bucket="1_2"} 323
telemt_desync_frames_bucket_total{bucket="3_10"} 682
telemt_desync_frames_bucket_total{bucket="gt_10"} 531
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 6458
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 6257
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 444445
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 4738309681 (4.41 GB)
telemt_user_octets_to_client{user="hello"} 140534207652 (130.88 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 165049.3 (45h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3158598
telemt_connections_bad_total 29294
telemt_handshake_timeouts_total 212582
telemt_upstream_connect_attempt_total 36658
telemt_upstream_connect_success_total 36643
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 36658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17498
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 10184
telemt_me_reconnect_attempts_total 30660
telemt_me_reconnect_success_total 28097
telemt_me_reader_eof_total 29783
telemt_me_idle_close_by_peer_total 29782
telemt_me_route_drop_no_conn_total 1081121
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2612056
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8724
telemt_desync_full_logged_total 2887
telemt_desync_suppressed_total 5837
telemt_desync_frames_bucket_total{bucket="1_2"} 1434
telemt_desync_frames_bucket_total{bucket="3_10"} 3193
telemt_desync_frames_bucket_total{bucket="gt_10"} 4097
telemt_pool_swap_total 155
telemt_me_writer_removed_unexpected_total 28434
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 28056
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 337
telemt_user_connections_total{user="hello"} 2611341
telemt_user_connections_current{user="hello"} 811
telemt_user_octets_from_client{user="hello"} 43248325068 (40.28 GB)
telemt_user_octets_to_client{user="hello"} 917145224413 (854.16 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 165049.5 (45h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2037269
telemt_connections_bad_total 22122
telemt_handshake_timeouts_total 186950
telemt_upstream_connect_attempt_total 51844
telemt_upstream_connect_success_total 49409
telemt_upstream_connect_fail_total 2298
telemt_upstream_connect_attempts_per_request{bucket="1"} 51570
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19432
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2297
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20184
telemt_me_reconnect_attempts_total 43161
telemt_me_reconnect_success_total 34154
telemt_me_reader_eof_total 36664
telemt_me_idle_close_by_peer_total 36657
telemt_me_route_drop_no_conn_total 723093
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1682499
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3611
telemt_desync_full_logged_total 1149
telemt_desync_suppressed_total 2462
telemt_desync_frames_bucket_total{bucket="1_2"} 952
telemt_desync_frames_bucket_total{bucket="3_10"} 1504
telemt_desync_frames_bucket_total{bucket="gt_10"} 1155
telemt_pool_swap_total 144
telemt_me_writer_removed_unexpected_total 34719
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 34130
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 565
telemt_user_connections_total{user="hello"} 1688368
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 25840534535 (24.07 GB)
telemt_user_octets_to_client{user="hello"} 637358245310 (593.59 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 34485.0 (9h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 549218
telemt_connections_bad_total 5661
telemt_handshake_timeouts_total 5406
telemt_upstream_connect_attempt_total 7441
telemt_upstream_connect_success_total 7197
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 7441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3764
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 958
telemt_me_reconnect_attempts_total 26378
telemt_me_reconnect_success_total 5442
telemt_me_reader_eof_total 6203
telemt_me_idle_close_by_peer_total 6202
telemt_me_route_drop_no_conn_total 208611
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 514402
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1456
telemt_desync_full_logged_total 453
telemt_desync_suppressed_total 1003
telemt_desync_frames_bucket_total{bucket="1_2"} 440
telemt_desync_frames_bucket_total{bucket="3_10"} 583
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6139
telemt_me_refill_failed_total 652
telemt_me_writer_restored_same_endpoint_total 5438
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 697
telemt_user_connections_total{user="hello"} 514375
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 5993325544 (5.58 GB)
telemt_user_octets_to_client{user="hello"} 165210800808 (153.86 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 60
```