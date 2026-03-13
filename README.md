# Server Metrics 2026-03-13 19:45:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 136040.0 (37h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4341472
telemt_connections_bad_total 37800
telemt_handshake_timeouts_total 105661
telemt_upstream_connect_attempt_total 28515
telemt_upstream_connect_success_total 28321
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 28515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_timeout_total 6527
telemt_me_reconnect_attempts_total 29293
telemt_me_reconnect_success_total 19177
telemt_me_reader_eof_total 20583
telemt_me_idle_close_by_peer_total 20582
telemt_me_route_drop_no_conn_total 1632048
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3971286
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15631
telemt_desync_full_logged_total 4170
telemt_desync_suppressed_total 11461
telemt_desync_frames_bucket_total{bucket="1_2"} 3894
telemt_desync_frames_bucket_total{bucket="3_10"} 5962
telemt_desync_frames_bucket_total{bucket="gt_10"} 5775
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 19769
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19164
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 592
telemt_user_connections_total{user="hello"} 3973447
telemt_user_connections_current{user="hello"} 1435
telemt_user_octets_from_client{user="hello"} 57587525308 (53.63 GB)
telemt_user_octets_to_client{user="hello"} 1251997563613 (1.14 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 390
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 35704.0 (9h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 515308
telemt_connections_bad_total 40100
telemt_handshake_timeouts_total 11181
telemt_upstream_connect_attempt_total 10418
telemt_upstream_connect_success_total 10204
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 10418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4011
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_keepalive_timeout_total 1869
telemt_me_reconnect_attempts_total 9794
telemt_me_reconnect_success_total 6379
telemt_me_reader_eof_total 6747
telemt_me_idle_close_by_peer_total 6746
telemt_me_route_drop_no_conn_total 193163
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 447799
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1542
telemt_desync_full_logged_total 414
telemt_desync_suppressed_total 1128
telemt_desync_frames_bucket_total{bucket="1_2"} 326
telemt_desync_frames_bucket_total{bucket="3_10"} 684
telemt_desync_frames_bucket_total{bucket="gt_10"} 532
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 6573
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 6371
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 449729
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 4802634513 (4.47 GB)
telemt_user_octets_to_client{user="hello"} 141949723872 (132.20 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 165660.6 (46h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3168975
telemt_connections_bad_total 29295
telemt_handshake_timeouts_total 212935
telemt_upstream_connect_attempt_total 36718
telemt_upstream_connect_success_total 36702
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 36717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17518
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 10185
telemt_me_reconnect_attempts_total 30702
telemt_me_reconnect_success_total 28138
telemt_me_reader_eof_total 29823
telemt_me_idle_close_by_peer_total 29822
telemt_me_route_drop_no_conn_total 1084274
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2621833
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8740
telemt_desync_full_logged_total 2898
telemt_desync_suppressed_total 5842
telemt_desync_frames_bucket_total{bucket="1_2"} 1439
telemt_desync_frames_bucket_total{bucket="3_10"} 3198
telemt_desync_frames_bucket_total{bucket="gt_10"} 4103
telemt_pool_swap_total 155
telemt_me_writer_removed_unexpected_total 28475
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 28097
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 337
telemt_user_connections_total{user="hello"} 2621118
telemt_user_connections_current{user="hello"} 805
telemt_user_octets_from_client{user="hello"} 43397573928 (40.42 GB)
telemt_user_octets_to_client{user="hello"} 922835668825 (859.46 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 165661.0 (46h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2045775
telemt_connections_bad_total 22122
telemt_handshake_timeouts_total 188471
telemt_upstream_connect_attempt_total 51971
telemt_upstream_connect_success_total 49536
telemt_upstream_connect_fail_total 2298
telemt_upstream_connect_attempts_per_request{bucket="1"} 51697
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2297
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20186
telemt_me_reconnect_attempts_total 43272
telemt_me_reconnect_success_total 34265
telemt_me_reader_eof_total 36778
telemt_me_idle_close_by_peer_total 36771
telemt_me_route_drop_no_conn_total 725174
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1689047
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3636
telemt_desync_full_logged_total 1158
telemt_desync_suppressed_total 2478
telemt_desync_frames_bucket_total{bucket="1_2"} 958
telemt_desync_frames_bucket_total{bucket="3_10"} 1511
telemt_desync_frames_bucket_total{bucket="gt_10"} 1167
telemt_pool_swap_total 144
telemt_me_writer_removed_unexpected_total 34833
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 34241
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 1694916
telemt_user_connections_current{user="hello"} 615
telemt_user_octets_from_client{user="hello"} 25958342779 (24.18 GB)
telemt_user_octets_to_client{user="hello"} 638780109334 (594.91 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 35096.6 (9h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 555598
telemt_connections_bad_total 5682
telemt_handshake_timeouts_total 5435
telemt_upstream_connect_attempt_total 7527
telemt_upstream_connect_success_total 7283
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 7527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3816
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 960
telemt_me_reconnect_attempts_total 26464
telemt_me_reconnect_success_total 5528
telemt_me_reader_eof_total 6289
telemt_me_idle_close_by_peer_total 6288
telemt_me_route_drop_no_conn_total 210826
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 520575
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
telemt_me_writer_removed_unexpected_total 6225
telemt_me_refill_failed_total 652
telemt_me_writer_restored_same_endpoint_total 5524
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 697
telemt_user_connections_total{user="hello"} 520544
telemt_user_connections_current{user="hello"} 594
telemt_user_octets_from_client{user="hello"} 6058954624 (5.64 GB)
telemt_user_octets_to_client{user="hello"} 166517881308 (155.08 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 74
```