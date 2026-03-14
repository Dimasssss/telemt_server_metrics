# Server Metrics 2026-03-14 04:57:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 169145.5 (46h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4793152
telemt_connections_bad_total 39902
telemt_handshake_timeouts_total 110060
telemt_upstream_connect_attempt_total 35639
telemt_upstream_connect_success_total 35404
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 35639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15974
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_timeout_total 7301
telemt_me_reconnect_attempts_total 34814
telemt_me_reconnect_success_total 24670
telemt_me_reader_eof_total 26474
telemt_me_idle_close_by_peer_total 26473
telemt_me_route_drop_no_conn_total 1815585
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4397230
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16955
telemt_desync_full_logged_total 4581
telemt_desync_suppressed_total 12374
telemt_desync_frames_bucket_total{bucket="1_2"} 4230
telemt_desync_frames_bucket_total{bucket="3_10"} 6473
telemt_desync_frames_bucket_total{bucket="gt_10"} 6252
telemt_pool_swap_total 147
telemt_me_writer_removed_unexpected_total 25336
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24657
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 666
telemt_user_connections_total{user="hello"} 4398801
telemt_user_connections_current{user="hello"} 962
telemt_user_octets_from_client{user="hello"} 64249507140 (59.84 GB)
telemt_user_octets_to_client{user="hello"} 1386195331001 (1.26 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 68809.3 (19h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 752079
telemt_connections_bad_total 52863
telemt_handshake_timeouts_total 13768
telemt_upstream_connect_attempt_total 18945
telemt_upstream_connect_success_total 18681
telemt_upstream_connect_fail_total 264
telemt_upstream_connect_attempts_per_request{bucket="1"} 18945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8089
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 264
telemt_me_keepalive_timeout_total 2107
telemt_me_reconnect_attempts_total 16673
telemt_me_reconnect_success_total 13217
telemt_me_reader_eof_total 14042
telemt_me_idle_close_by_peer_total 14041
telemt_me_route_drop_no_conn_total 248087
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 597020
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1780
telemt_desync_full_logged_total 525
telemt_desync_suppressed_total 1255
telemt_desync_frames_bucket_total{bucket="1_2"} 373
telemt_desync_frames_bucket_total{bucket="3_10"} 791
telemt_desync_frames_bucket_total{bucket="gt_10"} 616
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 13506
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 13209
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 289
telemt_user_connections_total{user="hello"} 598971
telemt_user_connections_current{user="hello"} 281
telemt_user_octets_from_client{user="hello"} 6405339941 (5.97 GB)
telemt_user_octets_to_client{user="hello"} 199011990656 (185.34 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 198766.0 (55h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3448689
telemt_connections_bad_total 37134
telemt_handshake_timeouts_total 228085
telemt_upstream_connect_attempt_total 44944
telemt_upstream_connect_success_total 44923
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 44944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21034
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10610
telemt_me_reconnect_attempts_total 39707
telemt_me_reconnect_success_total 34737
telemt_me_reader_eof_total 36902
telemt_me_idle_close_by_peer_total 36901
telemt_me_route_drop_no_conn_total 1179125
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2873584
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9525
telemt_desync_full_logged_total 3199
telemt_desync_suppressed_total 6326
telemt_desync_frames_bucket_total{bucket="1_2"} 1649
telemt_desync_frames_bucket_total{bucket="3_10"} 3450
telemt_desync_frames_bucket_total{bucket="gt_10"} 4426
telemt_pool_swap_total 188
telemt_me_writer_removed_unexpected_total 35220
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 34696
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 483
telemt_user_connections_total{user="hello"} 2872797
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 45860561588 (42.71 GB)
telemt_user_octets_to_client{user="hello"} 1030164560381 (959.42 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 198768.7 (55h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2312852
telemt_connections_bad_total 23088
telemt_handshake_timeouts_total 261972
telemt_upstream_connect_attempt_total 62120
telemt_upstream_connect_success_total 59644
telemt_upstream_connect_fail_total 2339
telemt_upstream_connect_attempts_per_request{bucket="1"} 61846
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23849
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2338
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20466
telemt_me_reconnect_attempts_total 51786
telemt_me_reconnect_success_total 42746
telemt_me_reader_eof_total 45849
telemt_me_idle_close_by_peer_total 45842
telemt_me_route_drop_no_conn_total 784075
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1833831
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3884
telemt_desync_full_logged_total 1251
telemt_desync_suppressed_total 2633
telemt_desync_frames_bucket_total{bucket="1_2"} 1045
telemt_desync_frames_bucket_total{bucket="3_10"} 1614
telemt_desync_frames_bucket_total{bucket="gt_10"} 1225
telemt_pool_swap_total 176
telemt_me_writer_removed_unexpected_total 43399
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 42722
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 653
telemt_user_connections_total{user="hello"} 1839797
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 27877903339 (25.96 GB)
telemt_user_octets_to_client{user="hello"} 675073576378 (628.71 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 68202.1 (18h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 739529
telemt_connections_bad_total 7982
telemt_handshake_timeouts_total 8902
telemt_upstream_connect_attempt_total 17604
telemt_upstream_connect_success_total 17140
telemt_upstream_connect_fail_total 464
telemt_upstream_connect_attempts_per_request{bucket="1"} 17604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9022
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 464
telemt_me_keepalive_timeout_total 1539
telemt_me_reconnect_attempts_total 52505
telemt_me_reconnect_success_total 13743
telemt_me_reader_eof_total 15302
telemt_me_idle_close_by_peer_total 15301
telemt_me_route_drop_no_conn_total 282410
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 690120
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1741
telemt_desync_full_logged_total 552
telemt_desync_suppressed_total 1189
telemt_desync_frames_bucket_total{bucket="1_2"} 515
telemt_desync_frames_bucket_total{bucket="3_10"} 681
telemt_desync_frames_bucket_total{bucket="gt_10"} 545
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 15072
telemt_me_refill_failed_total 1207
telemt_me_writer_restored_same_endpoint_total 13738
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1329
telemt_user_connections_total{user="hello"} 689987
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 12475781644 (11.62 GB)
telemt_user_octets_to_client{user="hello"} 223180065684 (207.85 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 45
```