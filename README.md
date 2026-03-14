# Server Metrics 2026-03-14 11:31:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 192789.8 (53h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5567073
telemt_connections_bad_total 57009
telemt_handshake_timeouts_total 122941
telemt_upstream_connect_attempt_total 40449
telemt_upstream_connect_success_total 40191
telemt_upstream_connect_fail_total 258
telemt_upstream_connect_attempts_per_request{bucket="1"} 40449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18251
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 258
telemt_me_keepalive_timeout_total 7718
telemt_me_reconnect_attempts_total 44619
telemt_me_reconnect_success_total 28248
telemt_me_reader_eof_total 30418
telemt_me_idle_close_by_peer_total 30417
telemt_me_route_drop_no_conn_total 2106214
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5106173
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19551
telemt_desync_full_logged_total 5340
telemt_desync_suppressed_total 14211
telemt_desync_frames_bucket_total{bucket="1_2"} 4755
telemt_desync_frames_bucket_total{bucket="3_10"} 7454
telemt_desync_frames_bucket_total{bucket="gt_10"} 7342
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 29171
telemt_me_refill_failed_total 506
telemt_me_writer_restored_same_endpoint_total 28235
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 923
telemt_user_connections_total{user="hello"} 5107609
telemt_user_connections_current{user="hello"} 1763
telemt_user_octets_from_client{user="hello"} 79060751828 (73.63 GB)
telemt_user_octets_to_client{user="hello"} 1626606707121 (1.48 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 469
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 92453.7 (25h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1056316
telemt_connections_bad_total 58876
telemt_handshake_timeouts_total 24371
telemt_upstream_connect_attempt_total 24163
telemt_upstream_connect_success_total 23867
telemt_upstream_connect_fail_total 296
telemt_upstream_connect_attempts_per_request{bucket="1"} 24163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10561
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 261
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 296
telemt_me_keepalive_timeout_total 2299
telemt_me_reconnect_attempts_total 30895
telemt_me_reconnect_success_total 17239
telemt_me_reader_eof_total 18555
telemt_me_idle_close_by_peer_total 18554
telemt_me_route_drop_no_conn_total 356205
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 866619
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2423
telemt_desync_full_logged_total 758
telemt_desync_suppressed_total 1665
telemt_desync_frames_bucket_total{bucket="1_2"} 606
telemt_desync_frames_bucket_total{bucket="3_10"} 1017
telemt_desync_frames_bucket_total{bucket="gt_10"} 800
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 17910
telemt_me_refill_failed_total 420
telemt_me_writer_restored_same_endpoint_total 17231
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 671
telemt_user_connections_total{user="hello"} 868533
telemt_user_connections_current{user="hello"} 729
telemt_user_octets_from_client{user="hello"} 9484860473 (8.83 GB)
telemt_user_octets_to_client{user="hello"} 304640920184 (283.72 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 222410.3 (61h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3947575
telemt_connections_bad_total 46183
telemt_handshake_timeouts_total 264698
telemt_upstream_connect_attempt_total 50213
telemt_upstream_connect_success_total 50192
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 50213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23426
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 255
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11099
telemt_me_reconnect_attempts_total 44774
telemt_me_reconnect_success_total 38775
telemt_me_reader_eof_total 41177
telemt_me_idle_close_by_peer_total 41175
telemt_me_route_drop_no_conn_total 1356685
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3301901
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10635
telemt_desync_full_logged_total 3595
telemt_desync_suppressed_total 7040
telemt_desync_frames_bucket_total{bucket="1_2"} 1934
telemt_desync_frames_bucket_total{bucket="3_10"} 3848
telemt_desync_frames_bucket_total{bucket="gt_10"} 4853
telemt_pool_swap_total 206
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 39349
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 38734
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 574
telemt_user_connections_total{user="hello"} 3301050
telemt_user_connections_current{user="hello"} 1028
telemt_user_octets_from_client{user="hello"} 56179419884 (52.32 GB)
telemt_user_octets_to_client{user="hello"} 1182846020905 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 222412.9 (61h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2589370
telemt_connections_bad_total 23477
telemt_handshake_timeouts_total 330479
telemt_upstream_connect_attempt_total 68789
telemt_upstream_connect_success_total 66282
telemt_upstream_connect_fail_total 2370
telemt_upstream_connect_attempts_per_request{bucket="1"} 68515
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26629
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2369
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20807
telemt_me_reconnect_attempts_total 60943
telemt_me_reconnect_success_total 48165
telemt_me_reader_eof_total 51608
telemt_me_idle_close_by_peer_total 51600
telemt_me_route_drop_no_conn_total 862085
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2026270
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4090
telemt_desync_full_logged_total 1343
telemt_desync_suppressed_total 2747
telemt_desync_frames_bucket_total{bucket="1_2"} 1163
telemt_desync_frames_bucket_total{bucket="3_10"} 1668
telemt_desync_frames_bucket_total{bucket="gt_10"} 1259
telemt_pool_swap_total 190
telemt_me_writer_removed_unexpected_total 48982
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 48140
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 817
telemt_user_connections_total{user="hello"} 2032623
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 30161430607 (28.09 GB)
telemt_user_octets_to_client{user="hello"} 727596909462 (677.63 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 91846.4 (25h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1041913
telemt_connections_bad_total 18076
telemt_handshake_timeouts_total 13658
telemt_upstream_connect_attempt_total 22589
telemt_upstream_connect_success_total 21978
telemt_upstream_connect_fail_total 611
telemt_upstream_connect_attempts_per_request{bucket="1"} 22589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11408
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 611
telemt_me_keepalive_timeout_total 1742
telemt_me_reconnect_attempts_total 79722
telemt_me_reconnect_success_total 17405
telemt_me_reader_eof_total 19761
telemt_me_idle_close_by_peer_total 19760
telemt_me_route_drop_no_conn_total 421715
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 963953
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2600
telemt_desync_full_logged_total 812
telemt_desync_suppressed_total 1788
telemt_desync_frames_bucket_total{bucket="1_2"} 913
telemt_desync_frames_bucket_total{bucket="3_10"} 937
telemt_desync_frames_bucket_total{bucket="gt_10"} 750
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19510
telemt_me_refill_failed_total 1942
telemt_me_writer_restored_same_endpoint_total 17400
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2105
telemt_user_connections_total{user="hello"} 963167
telemt_user_connections_current{user="hello"} 615
telemt_user_octets_from_client{user="hello"} 16908935524 (15.75 GB)
telemt_user_octets_to_client{user="hello"} 325759058920 (303.39 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 83
```