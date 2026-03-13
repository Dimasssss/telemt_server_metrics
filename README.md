# Server Metrics 2026-03-13 07:45:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 92823.5 (25h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2560479
telemt_connections_bad_total 36169
telemt_handshake_timeouts_total 26758
telemt_upstream_connect_attempt_total 18088
telemt_upstream_connect_success_total 17987
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 18088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 1359
telemt_me_reconnect_attempts_total 22229
telemt_me_reconnect_success_total 13356
telemt_me_reader_eof_total 14396
telemt_me_idle_close_by_peer_total 14395
telemt_me_route_drop_no_conn_total 959747
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2344967
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10580
telemt_desync_full_logged_total 2726
telemt_desync_suppressed_total 7854
telemt_desync_frames_bucket_total{bucket="1_2"} 2698
telemt_desync_frames_bucket_total{bucket="3_10"} 3915
telemt_desync_frames_bucket_total{bucket="gt_10"} 3967
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 13820
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13343
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 2344464
telemt_user_connections_current{user="hello"} 1604
telemt_user_octets_from_client{user="hello"} 33469596252 (31.17 GB)
telemt_user_octets_to_client{user="hello"} 787456261276 (733.38 GB)
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 122444.1 (34h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1034607
telemt_connections_bad_total 13195
telemt_handshake_timeouts_total 66169
telemt_upstream_connect_attempt_total 30669
telemt_upstream_connect_success_total 30638
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 30669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14738
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3616
telemt_me_reconnect_attempts_total 23039
telemt_me_reconnect_success_total 22919
telemt_me_reader_eof_total 24425
telemt_me_idle_close_by_peer_total 24425
telemt_me_route_drop_no_conn_total 323615
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 915227
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4024
telemt_desync_full_logged_total 1232
telemt_desync_suppressed_total 2792
telemt_desync_frames_bucket_total{bucket="1_2"} 1524
telemt_desync_frames_bucket_total{bucket="3_10"} 1297
telemt_desync_frames_bucket_total{bucket="gt_10"} 1203
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 23144
telemt_me_writer_restored_same_endpoint_total 22910
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 225
telemt_user_connections_total{user="hello"} 917154
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 14095353616 (13.13 GB)
telemt_user_octets_to_client{user="hello"} 343822458119 (320.21 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 122443.9 (34h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2071473
telemt_connections_bad_total 23383
telemt_handshake_timeouts_total 138856
telemt_upstream_connect_attempt_total 28136
telemt_upstream_connect_success_total 28125
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 28135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13272
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1740
telemt_me_reconnect_attempts_total 22971
telemt_me_reconnect_success_total 21695
telemt_me_reader_eof_total 22983
telemt_me_idle_close_by_peer_total 22982
telemt_me_route_drop_no_conn_total 666592
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1643067
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5547
telemt_desync_full_logged_total 1730
telemt_desync_suppressed_total 3817
telemt_desync_frames_bucket_total{bucket="1_2"} 913
telemt_desync_frames_bucket_total{bucket="3_10"} 2017
telemt_desync_frames_bucket_total{bucket="gt_10"} 2617
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 21906
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21654
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 1642545
telemt_user_connections_current{user="hello"} 821
telemt_user_octets_from_client{user="hello"} 27334405812 (25.46 GB)
telemt_user_octets_to_client{user="hello"} 597548581249 (556.51 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 122444.4 (34h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1281467
telemt_connections_bad_total 14141
telemt_handshake_timeouts_total 81710
telemt_upstream_connect_attempt_total 41131
telemt_upstream_connect_success_total 38834
telemt_upstream_connect_fail_total 2160
telemt_upstream_connect_attempts_per_request{bucket="1"} 40857
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2159
telemt_me_keepalive_timeout_total 11438
telemt_me_reconnect_attempts_total 35835
telemt_me_reconnect_success_total 26897
telemt_me_reader_eof_total 28975
telemt_me_idle_close_by_peer_total 28968
telemt_me_route_drop_no_conn_total 460082
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1094056
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2165
telemt_desync_full_logged_total 702
telemt_desync_suppressed_total 1463
telemt_desync_frames_bucket_total{bucket="1_2"} 592
telemt_desync_frames_bucket_total{bucket="3_10"} 834
telemt_desync_frames_bucket_total{bucket="gt_10"} 739
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 27362
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 26873
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 465
telemt_user_connections_total{user="hello"} 1098799
telemt_user_connections_current{user="hello"} 565
telemt_user_octets_from_client{user="hello"} 16703285129 (15.56 GB)
telemt_user_octets_to_client{user="hello"} 434632146238 (404.78 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 122444.2 (34h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1442184
telemt_connections_bad_total 26034
telemt_handshake_timeouts_total 11992
telemt_upstream_connect_attempt_total 38665
telemt_upstream_connect_success_total 38194
telemt_upstream_connect_fail_total 471
telemt_upstream_connect_attempts_per_request{bucket="1"} 38665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18606
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 471
telemt_me_keepalive_timeout_total 2118
telemt_me_reconnect_attempts_total 45864
telemt_me_reconnect_success_total 32125
telemt_me_reader_eof_total 33724
telemt_me_idle_close_by_peer_total 33724
telemt_me_seq_mismatch_total 44
telemt_me_route_drop_no_conn_total 529736
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1326041
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 48
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4699
telemt_desync_full_logged_total 1675
telemt_desync_suppressed_total 3024
telemt_desync_frames_bucket_total{bucket="1_2"} 1432
telemt_desync_frames_bucket_total{bucket="3_10"} 1514
telemt_desync_frames_bucket_total{bucket="gt_10"} 1753
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 32907
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 32069
telemt_me_writer_restored_fallback_total 56
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 782
telemt_user_connections_total{user="hello"} 1325849
telemt_user_connections_current{user="hello"} 817
telemt_user_octets_from_client{user="hello"} 16787306472 (15.63 GB)
telemt_user_octets_to_client{user="hello"} 453689196744 (422.53 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 102
```