# Server Metrics 2026-03-14 08:07:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 180507.0 (50h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5104693
telemt_connections_bad_total 42180
telemt_handshake_timeouts_total 116004
telemt_upstream_connect_attempt_total 37999
telemt_upstream_connect_success_total 37751
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 37999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17117
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_keepalive_timeout_total 7393
telemt_me_reconnect_attempts_total 37653
telemt_me_reconnect_success_total 26443
telemt_me_reader_eof_total 28385
telemt_me_idle_close_by_peer_total 28384
telemt_me_route_drop_no_conn_total 1931241
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4680311
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17832
telemt_desync_full_logged_total 4857
telemt_desync_suppressed_total 12975
telemt_desync_frames_bucket_total{bucket="1_2"} 4440
telemt_desync_frames_bucket_total{bucket="3_10"} 6777
telemt_desync_frames_bucket_total{bucket="gt_10"} 6615
telemt_pool_swap_total 157
telemt_me_writer_removed_unexpected_total 27176
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 26430
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 733
telemt_user_connections_total{user="hello"} 4681751
telemt_user_connections_current{user="hello"} 1637
telemt_user_octets_from_client{user="hello"} 71873422492 (66.94 GB)
telemt_user_octets_to_client{user="hello"} 1499028517909 (1.36 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 460
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 80170.5 (22h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 878158
telemt_connections_bad_total 53910
telemt_handshake_timeouts_total 16098
telemt_upstream_connect_attempt_total 21526
telemt_upstream_connect_success_total 21247
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 21526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_keepalive_timeout_total 2156
telemt_me_reconnect_attempts_total 18695
telemt_me_reconnect_success_total 15225
telemt_me_reader_eof_total 16175
telemt_me_idle_close_by_peer_total 16174
telemt_me_route_drop_no_conn_total 290631
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 707356
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2130
telemt_desync_full_logged_total 663
telemt_desync_suppressed_total 1467
telemt_desync_frames_bucket_total{bucket="1_2"} 459
telemt_desync_frames_bucket_total{bucket="3_10"} 928
telemt_desync_frames_bucket_total{bucket="gt_10"} 743
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 15554
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 15217
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 329
telemt_user_connections_total{user="hello"} 709265
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 7439850693 (6.93 GB)
telemt_user_octets_to_client{user="hello"} 244650069104 (227.85 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 210127.2 (58h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3647916
telemt_connections_bad_total 42987
telemt_handshake_timeouts_total 239388
telemt_upstream_connect_attempt_total 47508
telemt_upstream_connect_success_total 47487
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 47508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22164
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 245
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10764
telemt_me_reconnect_attempts_total 41702
telemt_me_reconnect_success_total 36719
telemt_me_reader_eof_total 38993
telemt_me_idle_close_by_peer_total 38992
telemt_me_route_drop_no_conn_total 1250571
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3045164
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9998
telemt_desync_full_logged_total 3370
telemt_desync_suppressed_total 6628
telemt_desync_frames_bucket_total{bucket="1_2"} 1759
telemt_desync_frames_bucket_total{bucket="3_10"} 3620
telemt_desync_frames_bucket_total{bucket="gt_10"} 4619
telemt_pool_swap_total 198
telemt_me_writer_removed_unexpected_total 37227
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 36678
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 508
telemt_user_connections_total{user="hello"} 3044300
telemt_user_connections_current{user="hello"} 868
telemt_user_octets_from_client{user="hello"} 51450620148 (47.92 GB)
telemt_user_octets_to_client{user="hello"} 1089702650949 (1014.86 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 210129.9 (58h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2426213
telemt_connections_bad_total 23323
telemt_handshake_timeouts_total 294821
telemt_upstream_connect_attempt_total 65394
telemt_upstream_connect_success_total 62898
telemt_upstream_connect_fail_total 2359
telemt_upstream_connect_attempts_per_request{bucket="1"} 65120
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25197
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2358
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20569
telemt_me_reconnect_attempts_total 54505
telemt_me_reconnect_success_total 45423
telemt_me_reader_eof_total 48672
telemt_me_idle_close_by_peer_total 48665
telemt_me_route_drop_no_conn_total 814684
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1908480
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3932
telemt_desync_full_logged_total 1281
telemt_desync_suppressed_total 2651
telemt_desync_frames_bucket_total{bucket="1_2"} 1083
telemt_desync_frames_bucket_total{bucket="3_10"} 1618
telemt_desync_frames_bucket_total{bucket="gt_10"} 1231
telemt_pool_swap_total 186
telemt_me_writer_removed_unexpected_total 46096
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 45399
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 673
telemt_user_connections_total{user="hello"} 1914593
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 28681007855 (26.71 GB)
telemt_user_octets_to_client{user="hello"} 698235404938 (650.28 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 79563.3 (22h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 856038
telemt_connections_bad_total 9005
telemt_handshake_timeouts_total 10102
telemt_upstream_connect_attempt_total 20207
telemt_upstream_connect_success_total 19665
telemt_upstream_connect_fail_total 542
telemt_upstream_connect_attempts_per_request{bucket="1"} 20207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10217
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 542
telemt_me_keepalive_timeout_total 1601
telemt_me_reconnect_attempts_total 66224
telemt_me_reconnect_success_total 15694
telemt_me_reader_eof_total 17646
telemt_me_idle_close_by_peer_total 17645
telemt_me_route_drop_no_conn_total 328632
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 799231
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2014
telemt_desync_full_logged_total 638
telemt_desync_suppressed_total 1376
telemt_desync_frames_bucket_total{bucket="1_2"} 640
telemt_desync_frames_bucket_total{bucket="3_10"} 761
telemt_desync_frames_bucket_total{bucket="gt_10"} 613
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 17408
telemt_me_refill_failed_total 1574
telemt_me_writer_restored_same_endpoint_total 15689
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1714
telemt_user_connections_total{user="hello"} 799088
telemt_user_connections_current{user="hello"} 738
telemt_user_octets_from_client{user="hello"} 14259735512 (13.28 GB)
telemt_user_octets_to_client{user="hello"} 267907139188 (249.51 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 92
```