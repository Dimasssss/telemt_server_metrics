# Server Metrics 2026-03-14 11:01:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 190948.5 (53h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5495055
telemt_connections_bad_total 56130
telemt_handshake_timeouts_total 121070
telemt_upstream_connect_attempt_total 40124
telemt_upstream_connect_success_total 39867
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 40124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_keepalive_timeout_total 7632
telemt_me_reconnect_attempts_total 43618
telemt_me_reconnect_success_total 28015
telemt_me_reader_eof_total 30145
telemt_me_idle_close_by_peer_total 30144
telemt_me_route_drop_no_conn_total 2078406
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5038495
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19234
telemt_desync_full_logged_total 5273
telemt_desync_suppressed_total 13961
telemt_desync_frames_bucket_total{bucket="1_2"} 4697
telemt_desync_frames_bucket_total{bucket="3_10"} 7334
telemt_desync_frames_bucket_total{bucket="gt_10"} 7203
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 28911
telemt_me_refill_failed_total 482
telemt_me_writer_restored_same_endpoint_total 28002
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 896
telemt_user_connections_total{user="hello"} 5039952
telemt_user_connections_current{user="hello"} 1717
telemt_user_octets_from_client{user="hello"} 77501952452 (72.18 GB)
telemt_user_octets_to_client{user="hello"} 1604481666937 (1.46 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 90612.3 (25h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1028704
telemt_connections_bad_total 58367
telemt_handshake_timeouts_total 22792
telemt_upstream_connect_attempt_total 23849
telemt_upstream_connect_success_total 23555
telemt_upstream_connect_fail_total 294
telemt_upstream_connect_attempts_per_request{bucket="1"} 23849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10445
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 258
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 294
telemt_me_keepalive_timeout_total 2295
telemt_me_reconnect_attempts_total 28016
telemt_me_reconnect_success_total 17017
telemt_me_reader_eof_total 18250
telemt_me_idle_close_by_peer_total 18249
telemt_me_route_drop_no_conn_total 346546
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 842190
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2394
telemt_desync_full_logged_total 743
telemt_desync_suppressed_total 1651
telemt_desync_frames_bucket_total{bucket="1_2"} 585
telemt_desync_frames_bucket_total{bucket="3_10"} 1012
telemt_desync_frames_bucket_total{bucket="gt_10"} 797
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 17605
telemt_me_refill_failed_total 337
telemt_me_writer_restored_same_endpoint_total 17009
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 588
telemt_user_connections_total{user="hello"} 844087
telemt_user_connections_current{user="hello"} 704
telemt_user_octets_from_client{user="hello"} 9165988325 (8.54 GB)
telemt_user_octets_to_client{user="hello"} 295213764536 (274.94 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 220569.2 (61h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3902004
telemt_connections_bad_total 45828
telemt_handshake_timeouts_total 259792
telemt_upstream_connect_attempt_total 49773
telemt_upstream_connect_success_total 49752
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 49773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23213
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11046
telemt_me_reconnect_attempts_total 44440
telemt_me_reconnect_success_total 38445
telemt_me_reader_eof_total 40833
telemt_me_idle_close_by_peer_total 40831
telemt_me_route_drop_no_conn_total 1340646
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3262742
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10469
telemt_desync_full_logged_total 3553
telemt_desync_suppressed_total 6916
telemt_desync_frames_bucket_total{bucket="1_2"} 1892
telemt_desync_frames_bucket_total{bucket="3_10"} 3792
telemt_desync_frames_bucket_total{bucket="gt_10"} 4785
telemt_pool_swap_total 204
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 39015
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 38404
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 570
telemt_user_connections_total{user="hello"} 3261900
telemt_user_connections_current{user="hello"} 1028
telemt_user_octets_from_client{user="hello"} 55073209180 (51.29 GB)
telemt_user_octets_to_client{user="hello"} 1167373380165 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 220571.7 (61h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2565430
telemt_connections_bad_total 23449
telemt_handshake_timeouts_total 325685
telemt_upstream_connect_attempt_total 68337
telemt_upstream_connect_success_total 65832
telemt_upstream_connect_fail_total 2368
telemt_upstream_connect_attempts_per_request{bucket="1"} 68063
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26427
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2367
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20783
telemt_me_reconnect_attempts_total 59483
telemt_me_reconnect_success_total 47823
telemt_me_reader_eof_total 51213
telemt_me_idle_close_by_peer_total 51205
telemt_me_route_drop_no_conn_total 854476
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2008553
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4061
telemt_desync_full_logged_total 1331
telemt_desync_suppressed_total 2730
telemt_desync_frames_bucket_total{bucket="1_2"} 1149
telemt_desync_frames_bucket_total{bucket="3_10"} 1658
telemt_desync_frames_bucket_total{bucket="gt_10"} 1254
telemt_pool_swap_total 189
telemt_me_writer_removed_unexpected_total 48603
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 47799
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 780
telemt_user_connections_total{user="hello"} 2014838
telemt_user_connections_current{user="hello"} 530
telemt_user_octets_from_client{user="hello"} 29909516851 (27.86 GB)
telemt_user_octets_to_client{user="hello"} 722991634738 (673.34 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 90005.4 (25h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1015207
telemt_connections_bad_total 17956
telemt_handshake_timeouts_total 13338
telemt_upstream_connect_attempt_total 22332
telemt_upstream_connect_success_total 21729
telemt_upstream_connect_fail_total 603
telemt_upstream_connect_attempts_per_request{bucket="1"} 22332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 603
telemt_me_keepalive_timeout_total 1722
telemt_me_reconnect_attempts_total 76823
telemt_me_reconnect_success_total 17258
telemt_me_reader_eof_total 19529
telemt_me_idle_close_by_peer_total 19528
telemt_me_route_drop_no_conn_total 394949
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 939082
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2542
telemt_desync_full_logged_total 793
telemt_desync_suppressed_total 1749
telemt_desync_frames_bucket_total{bucket="1_2"} 877
telemt_desync_frames_bucket_total{bucket="3_10"} 929
telemt_desync_frames_bucket_total{bucket="gt_10"} 736
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19277
telemt_me_refill_failed_total 1856
telemt_me_writer_restored_same_endpoint_total 17253
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2019
telemt_user_connections_total{user="hello"} 939019
telemt_user_connections_current{user="hello"} 686
telemt_user_octets_from_client{user="hello"} 16680440044 (15.53 GB)
telemt_user_octets_to_client{user="hello"} 315339363948 (293.68 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 105
```