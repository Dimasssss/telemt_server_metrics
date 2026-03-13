# Server Metrics 2026-03-13 21:12:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 141235.3 (39h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4461095
telemt_connections_bad_total 38122
telemt_handshake_timeouts_total 106366
telemt_upstream_connect_attempt_total 29497
telemt_upstream_connect_success_total 29295
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 29497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13050
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_timeout_total 6613
telemt_me_reconnect_attempts_total 30049
telemt_me_reconnect_success_total 19931
telemt_me_reader_eof_total 21378
telemt_me_idle_close_by_peer_total 21377
telemt_me_route_drop_no_conn_total 1681822
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4086159
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16276
telemt_desync_full_logged_total 4346
telemt_desync_suppressed_total 11930
telemt_desync_frames_bucket_total{bucket="1_2"} 4065
telemt_desync_frames_bucket_total{bucket="3_10"} 6212
telemt_desync_frames_bucket_total{bucket="gt_10"} 5999
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 20533
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19918
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 602
telemt_user_connections_total{user="hello"} 4088290
telemt_user_connections_current{user="hello"} 1021
telemt_user_octets_from_client{user="hello"} 60228192344 (56.09 GB)
telemt_user_octets_to_client{user="hello"} 1291754229453 (1.17 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 40899.0 (11h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 564647
telemt_connections_bad_total 41413
telemt_handshake_timeouts_total 12237
telemt_upstream_connect_attempt_total 11705
telemt_upstream_connect_success_total 11483
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 11705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4558
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 195
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_keepalive_timeout_total 1895
telemt_me_reconnect_attempts_total 10815
telemt_me_reconnect_success_total 7392
telemt_me_reader_eof_total 7819
telemt_me_idle_close_by_peer_total 7818
telemt_me_route_drop_no_conn_total 207954
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 490179
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1636
telemt_desync_full_logged_total 440
telemt_desync_suppressed_total 1196
telemt_desync_frames_bucket_total{bucket="1_2"} 345
telemt_desync_frames_bucket_total{bucket="3_10"} 709
telemt_desync_frames_bucket_total{bucket="gt_10"} 582
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 7604
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 7384
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 492107
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 5286846401 (4.92 GB)
telemt_user_octets_to_client{user="hello"} 160462223456 (149.44 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 170855.7 (47h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3246930
telemt_connections_bad_total 30755
telemt_handshake_timeouts_total 218275
telemt_upstream_connect_attempt_total 37966
telemt_upstream_connect_success_total 37945
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 37966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17952
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10258
telemt_me_reconnect_attempts_total 34073
telemt_me_reconnect_success_total 29126
telemt_me_reader_eof_total 30905
telemt_me_idle_close_by_peer_total 30904
telemt_me_route_drop_no_conn_total 1111807
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2691799
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8886
telemt_desync_full_logged_total 2984
telemt_desync_suppressed_total 5902
telemt_desync_frames_bucket_total{bucket="1_2"} 1466
telemt_desync_frames_bucket_total{bucket="3_10"} 3235
telemt_desync_frames_bucket_total{bucket="gt_10"} 4185
telemt_pool_swap_total 157
telemt_me_writer_removed_unexpected_total 29553
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 29085
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 2691075
telemt_user_connections_current{user="hello"} 655
telemt_user_octets_from_client{user="hello"} 44196549144 (41.16 GB)
telemt_user_octets_to_client{user="hello"} 949747460761 (884.52 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 170856.3 (47h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2111685
telemt_connections_bad_total 22793
telemt_handshake_timeouts_total 206253
telemt_upstream_connect_attempt_total 53115
telemt_upstream_connect_success_total 50673
telemt_upstream_connect_fail_total 2305
telemt_upstream_connect_attempts_per_request{bucket="1"} 52841
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20106
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2304
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20222
telemt_me_reconnect_attempts_total 44166
telemt_me_reconnect_success_total 35155
telemt_me_reader_eof_total 37725
telemt_me_idle_close_by_peer_total 37718
telemt_me_route_drop_no_conn_total 744534
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1735645
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3747
telemt_desync_full_logged_total 1198
telemt_desync_suppressed_total 2549
telemt_desync_frames_bucket_total{bucket="1_2"} 993
telemt_desync_frames_bucket_total{bucket="3_10"} 1551
telemt_desync_frames_bucket_total{bucket="gt_10"} 1203
telemt_pool_swap_total 149
telemt_me_writer_removed_unexpected_total 35739
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 35131
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 584
telemt_user_connections_total{user="hello"} 1741516
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 26981833947 (25.13 GB)
telemt_user_octets_to_client{user="hello"} 653002907034 (608.16 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 40291.6 (11h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 602862
telemt_connections_bad_total 5823
telemt_handshake_timeouts_total 5615
telemt_upstream_connect_attempt_total 8827
telemt_upstream_connect_success_total 8540
telemt_upstream_connect_fail_total 287
telemt_upstream_connect_attempts_per_request{bucket="1"} 8827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4397
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 287
telemt_me_keepalive_timeout_total 973
telemt_me_reconnect_attempts_total 31140
telemt_me_reconnect_success_total 6519
telemt_me_reader_eof_total 7417
telemt_me_idle_close_by_peer_total 7416
telemt_me_route_drop_no_conn_total 228851
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 565658
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1486
telemt_desync_full_logged_total 463
telemt_desync_suppressed_total 1023
telemt_desync_frames_bucket_total{bucket="1_2"} 448
telemt_desync_frames_bucket_total{bucket="3_10"} 593
telemt_desync_frames_bucket_total{bucket="gt_10"} 445
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 7347
telemt_me_refill_failed_total 767
telemt_me_writer_restored_same_endpoint_total 6515
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 828
telemt_user_connections_total{user="hello"} 565574
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 8436233396 (7.86 GB)
telemt_user_octets_to_client{user="hello"} 180999837300 (168.57 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 65
```