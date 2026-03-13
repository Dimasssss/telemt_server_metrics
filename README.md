# Server Metrics 2026-03-13 12:01:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 108188.6 (30h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3201349
telemt_connections_bad_total 36473
telemt_handshake_timeouts_total 55912
telemt_upstream_connect_attempt_total 21497
telemt_upstream_connect_success_total 21380
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 21497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10319
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 1987
telemt_me_reconnect_attempts_total 26054
telemt_me_reconnect_success_total 15974
telemt_me_reader_eof_total 17173
telemt_me_idle_close_by_peer_total 17172
telemt_me_route_drop_no_conn_total 1186484
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2931003
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12503
telemt_desync_full_logged_total 3240
telemt_desync_suppressed_total 9263
telemt_desync_frames_bucket_total{bucket="1_2"} 3197
telemt_desync_frames_bucket_total{bucket="3_10"} 4694
telemt_desync_frames_bucket_total{bucket="gt_10"} 4612
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 16507
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 15961
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 533
telemt_user_connections_total{user="hello"} 2930939
telemt_user_connections_current{user="hello"} 1844
telemt_user_octets_from_client{user="hello"} 40593242132 (37.81 GB)
telemt_user_octets_to_client{user="hello"} 947497633732 (882.43 GB)
telemt_user_unique_ips_current{user="hello"} 477
telemt_user_unique_ips_recent_window{user="hello"} 267
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 7852.5 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103899
telemt_connections_bad_total 6346
telemt_handshake_timeouts_total 2379
telemt_upstream_connect_attempt_total 2045
telemt_upstream_connect_success_total 1975
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 2045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 948
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 2758
telemt_me_reconnect_success_total 1531
telemt_me_reader_eof_total 1598
telemt_me_idle_close_by_peer_total 1598
telemt_me_route_drop_no_conn_total 36592
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92644
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 185
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 132
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1579
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 1524
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 92667
telemt_user_connections_current{user="hello"} 667
telemt_user_octets_from_client{user="hello"} 909790540 (867.64 MB)
telemt_user_octets_to_client{user="hello"} 22770843840 (21.21 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 137809.2 (38h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2442565
telemt_connections_bad_total 25649
telemt_handshake_timeouts_total 162732
telemt_upstream_connect_attempt_total 31462
telemt_upstream_connect_success_total 31452
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 31462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14894
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3044
telemt_me_reconnect_attempts_total 26766
telemt_me_reconnect_success_total 24221
telemt_me_reader_eof_total 25667
telemt_me_idle_close_by_peer_total 25666
telemt_me_route_drop_no_conn_total 811286
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1977455
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6584
telemt_desync_full_logged_total 2126
telemt_desync_suppressed_total 4458
telemt_desync_frames_bucket_total{bucket="1_2"} 1041
telemt_desync_frames_bucket_total{bucket="3_10"} 2396
telemt_desync_frames_bucket_total{bucket="gt_10"} 3147
telemt_pool_swap_total 128
telemt_me_writer_removed_unexpected_total 24501
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24180
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 1976870
telemt_user_connections_current{user="hello"} 1084
telemt_user_octets_from_client{user="hello"} 33418715844 (31.12 GB)
telemt_user_octets_to_client{user="hello"} 707449415649 (658.86 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 137809.6 (38h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1552395
telemt_connections_bad_total 17830
telemt_handshake_timeouts_total 103920
telemt_upstream_connect_attempt_total 44718
telemt_upstream_connect_success_total 42401
telemt_upstream_connect_fail_total 2180
telemt_upstream_connect_attempts_per_request{bucket="1"} 44444
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2179
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11762
telemt_me_reconnect_attempts_total 38622
telemt_me_reconnect_success_total 29659
telemt_me_reader_eof_total 31894
telemt_me_idle_close_by_peer_total 31887
telemt_me_route_drop_no_conn_total 551338
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1296009
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2452
telemt_desync_full_logged_total 817
telemt_desync_suppressed_total 1635
telemt_desync_frames_bucket_total{bucket="1_2"} 668
telemt_desync_frames_bucket_total{bucket="3_10"} 940
telemt_desync_frames_bucket_total{bucket="gt_10"} 844
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 30156
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 29635
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 497
telemt_user_connections_total{user="hello"} 1300733
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 19432645213 (18.10 GB)
telemt_user_octets_to_client{user="hello"} 508554258906 (473.63 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 7245.6 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102812
telemt_connections_bad_total 533
telemt_handshake_timeouts_total 618
telemt_upstream_connect_attempt_total 1488
telemt_upstream_connect_success_total 1441
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 1488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 830
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 7734
telemt_me_reconnect_success_total 1040
telemt_me_reader_eof_total 1219
telemt_me_idle_close_by_peer_total 1219
telemt_me_route_drop_no_conn_total 39680
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98298
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 359
telemt_desync_full_logged_total 127
telemt_desync_suppressed_total 232
telemt_desync_frames_bucket_total{bucket="1_2"} 185
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_me_writer_removed_unexpected_total 1241
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 1036
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 98294
telemt_user_connections_current{user="hello"} 780
telemt_user_octets_from_client{user="hello"} 1161993196 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 32240243652 (30.03 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 108
```