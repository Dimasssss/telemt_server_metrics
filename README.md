# Server Metrics 2026-03-14 00:06:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 151662.1 (42h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4590158
telemt_connections_bad_total 38392
telemt_handshake_timeouts_total 107812
telemt_upstream_connect_attempt_total 31906
telemt_upstream_connect_success_total 31689
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 31906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_keepalive_timeout_total 6656
telemt_me_reconnect_attempts_total 31920
telemt_me_reconnect_success_total 21788
telemt_me_reader_eof_total 23372
telemt_me_idle_close_by_peer_total 23371
telemt_me_route_drop_no_conn_total 1735852
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4207093
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16613
telemt_desync_full_logged_total 4475
telemt_desync_suppressed_total 12138
telemt_desync_frames_bucket_total{bucket="1_2"} 4134
telemt_desync_frames_bucket_total{bucket="3_10"} 6356
telemt_desync_frames_bucket_total{bucket="gt_10"} 6123
telemt_pool_swap_total 129
telemt_me_writer_removed_unexpected_total 22420
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 21775
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 632
telemt_user_connections_total{user="hello"} 4208975
telemt_user_connections_current{user="hello"} 629
telemt_user_octets_from_client{user="hello"} 62114849596 (57.85 GB)
telemt_user_octets_to_client{user="hello"} 1330891097337 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 51325.6 (14h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 631493
telemt_connections_bad_total 46973
telemt_handshake_timeouts_total 12776
telemt_upstream_connect_attempt_total 14453
telemt_upstream_connect_success_total 14213
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 14453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5902
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_timeout_total 1927
telemt_me_reconnect_attempts_total 13064
telemt_me_reconnect_success_total 9625
telemt_me_reader_eof_total 10205
telemt_me_idle_close_by_peer_total 10204
telemt_me_route_drop_no_conn_total 223640
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 531486
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1643
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9870
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 9617
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 533437
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 5831651929 (5.43 GB)
telemt_user_octets_to_client{user="hello"} 173944594464 (162.00 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 181282.4 (50h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3327118
telemt_connections_bad_total 32558
telemt_handshake_timeouts_total 222206
telemt_upstream_connect_attempt_total 40459
telemt_upstream_connect_success_total 40438
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 40459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19040
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10347
telemt_me_reconnect_attempts_total 36043
telemt_me_reconnect_success_total 31087
telemt_me_reader_eof_total 33002
telemt_me_idle_close_by_peer_total 33001
telemt_me_route_drop_no_conn_total 1141849
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2765142
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9050
telemt_desync_full_logged_total 3045
telemt_desync_suppressed_total 6005
telemt_desync_frames_bucket_total{bucket="1_2"} 1523
telemt_desync_frames_bucket_total{bucket="3_10"} 3281
telemt_desync_frames_bucket_total{bucket="gt_10"} 4246
telemt_pool_swap_total 169
telemt_me_writer_removed_unexpected_total 31539
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 31046
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 452
telemt_user_connections_total{user="hello"} 2764389
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 44803773264 (41.73 GB)
telemt_user_octets_to_client{user="hello"} 980431569861 (913.10 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 181285.0 (50h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2198339
telemt_connections_bad_total 22861
telemt_handshake_timeouts_total 234388
telemt_upstream_connect_attempt_total 56426
telemt_upstream_connect_success_total 53971
telemt_upstream_connect_fail_total 2318
telemt_upstream_connect_attempts_per_request{bucket="1"} 56152
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21455
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2317
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20356
telemt_me_reconnect_attempts_total 46939
telemt_me_reconnect_success_total 37914
telemt_me_reader_eof_total 40674
telemt_me_idle_close_by_peer_total 40667
telemt_me_route_drop_no_conn_total 763322
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1775317
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3798
telemt_desync_full_logged_total 1218
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1004
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 159
telemt_me_writer_removed_unexpected_total 38524
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 37890
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 610
telemt_user_connections_total{user="hello"} 1781212
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 27370402387 (25.49 GB)
telemt_user_octets_to_client{user="hello"} 661958316850 (616.50 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 50718.6 (14h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 667204
telemt_connections_bad_total 7867
telemt_handshake_timeouts_total 8348
telemt_upstream_connect_attempt_total 12234
telemt_upstream_connect_success_total 11873
telemt_upstream_connect_fail_total 361
telemt_upstream_connect_attempts_per_request{bucket="1"} 12234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 361
telemt_me_keepalive_timeout_total 1453
telemt_me_reconnect_attempts_total 41469
telemt_me_reconnect_success_total 9312
telemt_me_reader_eof_total 10500
telemt_me_idle_close_by_peer_total 10499
telemt_me_route_drop_no_conn_total 251872
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 620702
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1638
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1125
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 641
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 10403
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 9307
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1091
telemt_user_connections_total{user="hello"} 620601
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 10168618940 (9.47 GB)
telemt_user_octets_to_client{user="hello"} 202314911944 (188.42 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 21
```