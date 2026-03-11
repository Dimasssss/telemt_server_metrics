# Server Metrics 2026-03-11 16:13:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 92769.7 (25h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2306795
telemt_connections_bad_total 40443
telemt_handshake_timeouts_total 53729
telemt_upstream_connect_attempt_total 19418
telemt_upstream_connect_success_total 19406
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 19418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9555
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5007
telemt_me_reconnect_attempts_total 32582
telemt_me_reconnect_success_total 14709
telemt_me_reader_eof_total 15948
telemt_me_idle_close_by_peer_total 15948
telemt_me_route_drop_no_conn_total 856059
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2109806
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10959
telemt_desync_full_logged_total 2988
telemt_desync_suppressed_total 7971
telemt_desync_frames_bucket_total{bucket="1_2"} 2713
telemt_desync_frames_bucket_total{bucket="3_10"} 4232
telemt_desync_frames_bucket_total{bucket="gt_10"} 4014
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 15430
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 14703
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 721
telemt_user_connections_total{user="hello"} 2108257
telemt_user_connections_current{user="hello"} 1287
telemt_user_octets_from_client{user="hello"} 28514741028 (26.56 GB)
telemt_user_octets_to_client{user="hello"} 595436789908 (554.54 GB)
telemt_user_unique_ips_current{user="hello"} 361
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 92826.5 (25h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 858207
telemt_connections_bad_total 14760
telemt_handshake_timeouts_total 63135
telemt_upstream_connect_attempt_total 29299
telemt_upstream_connect_success_total 26341
telemt_upstream_connect_fail_total 2958
telemt_upstream_connect_attempts_per_request{bucket="1"} 29299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11806
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2958
telemt_me_keepalive_timeout_total 2635
telemt_me_reconnect_attempts_total 20804
telemt_me_reconnect_success_total 18711
telemt_me_reader_eof_total 19813
telemt_me_idle_close_by_peer_total 19810
telemt_me_route_drop_no_conn_total 333218
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 725330
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2935
telemt_desync_full_logged_total 936
telemt_desync_suppressed_total 1999
telemt_desync_frames_bucket_total{bucket="1_2"} 907
telemt_desync_frames_bucket_total{bucket="3_10"} 1054
telemt_desync_frames_bucket_total{bucket="gt_10"} 974
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 18980
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 18688
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 727790
telemt_user_connections_current{user="hello"} 531
telemt_user_octets_from_client{user="hello"} 8350599406 (7.78 GB)
telemt_user_octets_to_client{user="hello"} 206126055108 (191.97 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 92826.3 (25h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1478040
telemt_connections_bad_total 8815
telemt_handshake_timeouts_total 125182
telemt_upstream_connect_attempt_total 24130
telemt_upstream_connect_success_total 23824
telemt_upstream_connect_fail_total 306
telemt_upstream_connect_attempts_per_request{bucket="1"} 24130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10836
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 306
telemt_me_keepalive_timeout_total 1693
telemt_me_reconnect_attempts_total 40563
telemt_me_reconnect_success_total 18059
telemt_me_reader_eof_total 19568
telemt_me_idle_close_by_peer_total 19568
telemt_me_route_drop_no_conn_total 540709
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1290499
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3395
telemt_desync_full_logged_total 1005
telemt_desync_suppressed_total 2390
telemt_desync_frames_bucket_total{bucket="1_2"} 845
telemt_desync_frames_bucket_total{bucket="3_10"} 1281
telemt_desync_frames_bucket_total{bucket="gt_10"} 1269
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 19007
telemt_me_refill_failed_total 698
telemt_me_writer_restored_same_endpoint_total 18047
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 948
telemt_user_connections_total{user="hello"} 1290212
telemt_user_connections_current{user="hello"} 765
telemt_user_octets_from_client{user="hello"} 15663895805 (14.59 GB)
telemt_user_octets_to_client{user="hello"} 391873801029 (364.96 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 92826.6 (25h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1066554
telemt_connections_bad_total 77973
telemt_handshake_timeouts_total 103445
telemt_upstream_connect_attempt_total 24905
telemt_upstream_connect_success_total 24905
telemt_upstream_connect_attempts_per_request{bucket="1"} 24905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1081
telemt_me_reconnect_attempts_total 21329
telemt_me_reconnect_success_total 20253
telemt_me_reader_eof_total 21470
telemt_me_idle_close_by_peer_total 21469
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 349144
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 853144
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1761
telemt_desync_full_logged_total 679
telemt_desync_suppressed_total 1082
telemt_desync_frames_bucket_total{bucket="1_2"} 638
telemt_desync_frames_bucket_total{bucket="3_10"} 615
telemt_desync_frames_bucket_total{bucket="gt_10"} 508
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 20499
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 20222
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 852461
telemt_user_connections_current{user="hello"} 586
telemt_user_octets_from_client{user="hello"} 10183779516 (9.48 GB)
telemt_user_octets_to_client{user="hello"} 251610774800 (234.33 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 92826.4 (25h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1175765
telemt_connections_bad_total 6945
telemt_handshake_timeouts_total 11754
telemt_upstream_connect_attempt_total 25334
telemt_upstream_connect_success_total 25220
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 25334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12139
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 2107
telemt_me_reconnect_attempts_total 24515
telemt_me_reconnect_success_total 20421
telemt_me_reader_eof_total 21516
telemt_me_idle_close_by_peer_total 21516
telemt_me_route_drop_no_conn_total 419902
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1070544
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4167
telemt_desync_full_logged_total 1489
telemt_desync_suppressed_total 2678
telemt_desync_frames_bucket_total{bucket="1_2"} 1383
telemt_desync_frames_bucket_total{bucket="3_10"} 1559
telemt_desync_frames_bucket_total{bucket="gt_10"} 1225
telemt_pool_swap_total 61
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20814
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 20421
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 393
telemt_user_connections_total{user="hello"} 1070246
telemt_user_connections_current{user="hello"} 742
telemt_user_octets_from_client{user="hello"} 20168399479 (18.78 GB)
telemt_user_octets_to_client{user="hello"} 372651270662 (347.06 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 101
```