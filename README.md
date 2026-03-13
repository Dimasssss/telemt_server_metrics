# Server Metrics 2026-03-13 21:32:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 142460.0 (39h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4482780
telemt_connections_bad_total 38133
telemt_handshake_timeouts_total 106523
telemt_upstream_connect_attempt_total 29791
telemt_upstream_connect_success_total 29585
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 29791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13178
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 6617
telemt_me_reconnect_attempts_total 30253
telemt_me_reconnect_success_total 20133
telemt_me_reader_eof_total 21605
telemt_me_idle_close_by_peer_total 21604
telemt_me_route_drop_no_conn_total 1690933
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4106879
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16359
telemt_desync_full_logged_total 4376
telemt_desync_suppressed_total 11983
telemt_desync_frames_bucket_total{bucket="1_2"} 4081
telemt_desync_frames_bucket_total{bucket="3_10"} 6252
telemt_desync_frames_bucket_total{bucket="gt_10"} 6026
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 20739
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 20120
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 606
telemt_user_connections_total{user="hello"} 4109008
telemt_user_connections_current{user="hello"} 964
telemt_user_octets_from_client{user="hello"} 60430072080 (56.28 GB)
telemt_user_octets_to_client{user="hello"} 1302017022741 (1.18 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 42123.6 (11h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 573627
telemt_connections_bad_total 41499
telemt_handshake_timeouts_total 12275
telemt_upstream_connect_attempt_total 11963
telemt_upstream_connect_success_total 11740
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 11963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4688
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 1899
telemt_me_reconnect_attempts_total 11028
telemt_me_reconnect_success_total 7604
telemt_me_reader_eof_total 8042
telemt_me_idle_close_by_peer_total 8041
telemt_me_route_drop_no_conn_total 210811
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 497810
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
telemt_me_writer_removed_unexpected_total 7817
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 7596
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 499737
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 5369316213 (5.00 GB)
telemt_user_octets_to_client{user="hello"} 163807183400 (152.56 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 172080.3 (47h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3262899
telemt_connections_bad_total 31217
telemt_handshake_timeouts_total 219072
telemt_upstream_connect_attempt_total 38213
telemt_upstream_connect_success_total 38192
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 38213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18058
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10260
telemt_me_reconnect_attempts_total 34233
telemt_me_reconnect_success_total 29284
telemt_me_reader_eof_total 31082
telemt_me_idle_close_by_peer_total 31081
telemt_me_route_drop_no_conn_total 1117116
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2706353
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8898
telemt_desync_full_logged_total 2988
telemt_desync_suppressed_total 5910
telemt_desync_frames_bucket_total{bucket="1_2"} 1468
telemt_desync_frames_bucket_total{bucket="3_10"} 3240
telemt_desync_frames_bucket_total{bucket="gt_10"} 4190
telemt_pool_swap_total 159
telemt_me_writer_removed_unexpected_total 29716
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 29243
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 432
telemt_user_connections_total{user="hello"} 2705625
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 44345740704 (41.30 GB)
telemt_user_octets_to_client{user="hello"} 953566259997 (888.08 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 172082.9 (47h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2122540
telemt_connections_bad_total 22806
telemt_handshake_timeouts_total 208992
telemt_upstream_connect_attempt_total 53484
telemt_upstream_connect_success_total 51040
telemt_upstream_connect_fail_total 2307
telemt_upstream_connect_attempts_per_request{bucket="1"} 53210
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2306
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20237
telemt_me_reconnect_attempts_total 44443
telemt_me_reconnect_success_total 35431
telemt_me_reader_eof_total 38024
telemt_me_idle_close_by_peer_total 38017
telemt_me_route_drop_no_conn_total 747576
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1742802
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3769
telemt_desync_full_logged_total 1203
telemt_desync_suppressed_total 2566
telemt_desync_frames_bucket_total{bucket="1_2"} 994
telemt_desync_frames_bucket_total{bucket="3_10"} 1570
telemt_desync_frames_bucket_total{bucket="gt_10"} 1205
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 36017
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 35407
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 586
telemt_user_connections_total{user="hello"} 1748681
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 27027421579 (25.17 GB)
telemt_user_octets_to_client{user="hello"} 654638054502 (609.68 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 41516.4 (11h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 612402
telemt_connections_bad_total 5842
telemt_handshake_timeouts_total 5652
telemt_upstream_connect_attempt_total 9192
telemt_upstream_connect_success_total 8890
telemt_upstream_connect_fail_total 302
telemt_upstream_connect_attempts_per_request{bucket="1"} 9192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4573
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 302
telemt_me_keepalive_timeout_total 974
telemt_me_reconnect_attempts_total 31408
telemt_me_reconnect_success_total 6787
telemt_me_reader_eof_total 7686
telemt_me_idle_close_by_peer_total 7685
telemt_me_route_drop_no_conn_total 232635
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 574152
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1507
telemt_desync_full_logged_total 471
telemt_desync_suppressed_total 1036
telemt_desync_frames_bucket_total{bucket="1_2"} 457
telemt_desync_frames_bucket_total{bucket="3_10"} 597
telemt_desync_frames_bucket_total{bucket="gt_10"} 453
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 7616
telemt_me_refill_failed_total 767
telemt_me_writer_restored_same_endpoint_total 6783
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 829
telemt_user_connections_total{user="hello"} 574064
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 8501956820 (7.92 GB)
telemt_user_octets_to_client{user="hello"} 182832968448 (170.28 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 41
```