# Server Metrics 2026-03-13 21:27:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 142153.3 (39h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4477522
telemt_connections_bad_total 38132
telemt_handshake_timeouts_total 106474
telemt_upstream_connect_attempt_total 29689
telemt_upstream_connect_success_total 29484
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 29689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_timeout_total 6616
telemt_me_reconnect_attempts_total 30195
telemt_me_reconnect_success_total 20076
telemt_me_reader_eof_total 21537
telemt_me_idle_close_by_peer_total 21536
telemt_me_route_drop_no_conn_total 1688962
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4101816
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16344
telemt_desync_full_logged_total 4369
telemt_desync_suppressed_total 11975
telemt_desync_frames_bucket_total{bucket="1_2"} 4079
telemt_desync_frames_bucket_total{bucket="3_10"} 6245
telemt_desync_frames_bucket_total{bucket="gt_10"} 6020
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 20680
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 20063
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 604
telemt_user_connections_total{user="hello"} 4103943
telemt_user_connections_current{user="hello"} 1011
telemt_user_octets_from_client{user="hello"} 60381031744 (56.23 GB)
telemt_user_octets_to_client{user="hello"} 1299253680385 (1.18 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 287
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 41816.9 (11h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 571829
telemt_connections_bad_total 41499
telemt_handshake_timeouts_total 12259
telemt_upstream_connect_attempt_total 11917
telemt_upstream_connect_success_total 11694
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 11917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4663
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 1897
telemt_me_reconnect_attempts_total 10982
telemt_me_reconnect_success_total 7558
telemt_me_reader_eof_total 7995
telemt_me_idle_close_by_peer_total 7994
telemt_me_route_drop_no_conn_total 209910
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 496272
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1640
telemt_desync_full_logged_total 442
telemt_desync_suppressed_total 1198
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 710
telemt_desync_frames_bucket_total{bucket="gt_10"} 582
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 7770
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 7550
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 498199
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 5343440121 (4.98 GB)
telemt_user_octets_to_client{user="hello"} 163064383316 (151.87 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 171773.4 (47h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3259079
telemt_connections_bad_total 31158
telemt_handshake_timeouts_total 218835
telemt_upstream_connect_attempt_total 38125
telemt_upstream_connect_success_total 38104
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 38125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10259
telemt_me_reconnect_attempts_total 34189
telemt_me_reconnect_success_total 29241
telemt_me_reader_eof_total 31031
telemt_me_idle_close_by_peer_total 31030
telemt_me_route_drop_no_conn_total 1115711
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2702857
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8898
telemt_desync_full_logged_total 2988
telemt_desync_suppressed_total 5910
telemt_desync_frames_bucket_total{bucket="1_2"} 1468
telemt_desync_frames_bucket_total{bucket="3_10"} 3240
telemt_desync_frames_bucket_total{bucket="gt_10"} 4190
telemt_pool_swap_total 158
telemt_me_writer_removed_unexpected_total 29672
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 29200
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 431
telemt_user_connections_total{user="hello"} 2702129
telemt_user_connections_current{user="hello"} 591
telemt_user_octets_from_client{user="hello"} 44319096292 (41.28 GB)
telemt_user_octets_to_client{user="hello"} 952622880925 (887.20 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 171776.2 (47h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2119515
telemt_connections_bad_total 22804
telemt_handshake_timeouts_total 208129
telemt_upstream_connect_attempt_total 53371
telemt_upstream_connect_success_total 50927
telemt_upstream_connect_fail_total 2307
telemt_upstream_connect_attempts_per_request{bucket="1"} 53097
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2306
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20233
telemt_me_reconnect_attempts_total 44374
telemt_me_reconnect_success_total 35362
telemt_me_reader_eof_total 37947
telemt_me_idle_close_by_peer_total 37940
telemt_me_route_drop_no_conn_total 746782
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1741276
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3764
telemt_desync_full_logged_total 1202
telemt_desync_suppressed_total 2562
telemt_desync_frames_bucket_total{bucket="1_2"} 993
telemt_desync_frames_bucket_total{bucket="3_10"} 1566
telemt_desync_frames_bucket_total{bucket="gt_10"} 1205
telemt_pool_swap_total 150
telemt_me_writer_removed_unexpected_total 35946
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 35338
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 584
telemt_user_connections_total{user="hello"} 1747147
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 27018690527 (25.16 GB)
telemt_user_octets_to_client{user="hello"} 654279429258 (609.35 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 41209.5 (11h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 610077
telemt_connections_bad_total 5840
telemt_handshake_timeouts_total 5647
telemt_upstream_connect_attempt_total 9100
telemt_upstream_connect_success_total 8802
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 9100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4524
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_keepalive_timeout_total 974
telemt_me_reconnect_attempts_total 31359
telemt_me_reconnect_success_total 6738
telemt_me_reader_eof_total 7636
telemt_me_idle_close_by_peer_total 7635
telemt_me_route_drop_no_conn_total 231439
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 572039
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1505
telemt_desync_full_logged_total 469
telemt_desync_suppressed_total 1036
telemt_desync_frames_bucket_total{bucket="1_2"} 455
telemt_desync_frames_bucket_total{bucket="3_10"} 597
telemt_desync_frames_bucket_total{bucket="gt_10"} 453
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 7566
telemt_me_refill_failed_total 767
telemt_me_writer_restored_same_endpoint_total 6734
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 828
telemt_user_connections_total{user="hello"} 571951
telemt_user_connections_current{user="hello"} 446
telemt_user_octets_from_client{user="hello"} 8478725612 (7.90 GB)
telemt_user_octets_to_client{user="hello"} 182318150444 (169.80 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 51
```