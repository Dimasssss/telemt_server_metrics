# Server Metrics 2026-03-13 21:22:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 141846.2 (39h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4471793
telemt_connections_bad_total 38132
telemt_handshake_timeouts_total 106426
telemt_upstream_connect_attempt_total 29659
telemt_upstream_connect_success_total 29454
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 29659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_timeout_total 6616
telemt_me_reconnect_attempts_total 30165
telemt_me_reconnect_success_total 20046
telemt_me_reader_eof_total 21507
telemt_me_idle_close_by_peer_total 21506
telemt_me_route_drop_no_conn_total 1686519
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4096419
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16328
telemt_desync_full_logged_total 4363
telemt_desync_suppressed_total 11965
telemt_desync_frames_bucket_total{bucket="1_2"} 4078
telemt_desync_frames_bucket_total{bucket="3_10"} 6236
telemt_desync_frames_bucket_total{bucket="gt_10"} 6014
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 20650
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 20033
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 604
telemt_user_connections_total{user="hello"} 4098546
telemt_user_connections_current{user="hello"} 943
telemt_user_octets_from_client{user="hello"} 60319077708 (56.18 GB)
telemt_user_octets_to_client{user="hello"} 1296871729377 (1.18 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 41510.1 (11h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 569554
telemt_connections_bad_total 41499
telemt_handshake_timeouts_total 12255
telemt_upstream_connect_attempt_total 11828
telemt_upstream_connect_success_total 11605
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 11828
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 1897
telemt_me_reconnect_attempts_total 10893
telemt_me_reconnect_success_total 7469
telemt_me_reader_eof_total 7897
telemt_me_idle_close_by_peer_total 7896
telemt_me_route_drop_no_conn_total 209298
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 494479
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
telemt_me_writer_removed_unexpected_total 7681
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 7461
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 496406
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 5327706977 (4.96 GB)
telemt_user_octets_to_client{user="hello"} 161673119704 (150.57 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 171466.8 (47h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3255192
telemt_connections_bad_total 31053
telemt_handshake_timeouts_total 218513
telemt_upstream_connect_attempt_total 38092
telemt_upstream_connect_success_total 38071
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 38092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10259
telemt_me_reconnect_attempts_total 34156
telemt_me_reconnect_success_total 29208
telemt_me_reader_eof_total 30996
telemt_me_idle_close_by_peer_total 30995
telemt_me_route_drop_no_conn_total 1114212
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2699398
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8893
telemt_desync_full_logged_total 2985
telemt_desync_suppressed_total 5908
telemt_desync_frames_bucket_total{bucket="1_2"} 1467
telemt_desync_frames_bucket_total{bucket="3_10"} 3238
telemt_desync_frames_bucket_total{bucket="gt_10"} 4188
telemt_pool_swap_total 158
telemt_me_writer_removed_unexpected_total 29637
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 29167
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 429
telemt_user_connections_total{user="hello"} 2698672
telemt_user_connections_current{user="hello"} 611
telemt_user_octets_from_client{user="hello"} 44271116432 (41.23 GB)
telemt_user_octets_to_client{user="hello"} 951488017629 (886.14 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 171469.4 (47h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2116851
telemt_connections_bad_total 22798
telemt_handshake_timeouts_total 207170
telemt_upstream_connect_attempt_total 53309
telemt_upstream_connect_success_total 50865
telemt_upstream_connect_fail_total 2307
telemt_upstream_connect_attempts_per_request{bucket="1"} 53035
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20210
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2306
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20224
telemt_me_reconnect_attempts_total 44312
telemt_me_reconnect_success_total 35299
telemt_me_reader_eof_total 37885
telemt_me_idle_close_by_peer_total 37878
telemt_me_route_drop_no_conn_total 746159
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1739648
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3761
telemt_desync_full_logged_total 1201
telemt_desync_suppressed_total 2560
telemt_desync_frames_bucket_total{bucket="1_2"} 993
telemt_desync_frames_bucket_total{bucket="3_10"} 1563
telemt_desync_frames_bucket_total{bucket="gt_10"} 1205
telemt_pool_swap_total 150
telemt_me_writer_removed_unexpected_total 35884
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 35275
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 585
telemt_user_connections_total{user="hello"} 1745519
telemt_user_connections_current{user="hello"} 343
telemt_user_octets_from_client{user="hello"} 27003071835 (25.15 GB)
telemt_user_octets_to_client{user="hello"} 653635958698 (608.75 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 40902.9 (11h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 607819
telemt_connections_bad_total 5839
telemt_handshake_timeouts_total 5643
telemt_upstream_connect_attempt_total 9024
telemt_upstream_connect_success_total 8726
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 9024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4481
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_keepalive_timeout_total 974
telemt_me_reconnect_attempts_total 31283
telemt_me_reconnect_success_total 6662
telemt_me_reader_eof_total 7560
telemt_me_idle_close_by_peer_total 7559
telemt_me_route_drop_no_conn_total 230579
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 570021
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1504
telemt_desync_full_logged_total 468
telemt_desync_suppressed_total 1036
telemt_desync_frames_bucket_total{bucket="1_2"} 455
telemt_desync_frames_bucket_total{bucket="3_10"} 597
telemt_desync_frames_bucket_total{bucket="gt_10"} 452
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 7490
telemt_me_refill_failed_total 767
telemt_me_writer_restored_same_endpoint_total 6658
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 828
telemt_user_connections_total{user="hello"} 569933
telemt_user_connections_current{user="hello"} 446
telemt_user_octets_from_client{user="hello"} 8466150852 (7.88 GB)
telemt_user_octets_to_client{user="hello"} 181849725572 (169.36 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 37
```