# Server Metrics 2026-03-13 20:21:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 138179.2 (38h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4394999
telemt_connections_bad_total 37846
telemt_handshake_timeouts_total 105991
telemt_upstream_connect_attempt_total 28936
telemt_upstream_connect_success_total 28739
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 28936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15840
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12760
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 6553
telemt_me_reconnect_attempts_total 29624
telemt_me_reconnect_success_total 19508
telemt_me_reader_eof_total 20936
telemt_me_idle_close_by_peer_total 20935
telemt_me_route_drop_no_conn_total 1654380
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4022576
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15940
telemt_desync_full_logged_total 4252
telemt_desync_suppressed_total 11688
telemt_desync_frames_bucket_total{bucket="1_2"} 3969
telemt_desync_frames_bucket_total{bucket="3_10"} 6080
telemt_desync_frames_bucket_total{bucket="gt_10"} 5891
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 20104
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19495
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 596
telemt_user_connections_total{user="hello"} 4024730
telemt_user_connections_current{user="hello"} 1277
telemt_user_octets_from_client{user="hello"} 58750750460 (54.72 GB)
telemt_user_octets_to_client{user="hello"} 1269811232601 (1.15 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 357
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 37843.0 (10h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 539705
telemt_connections_bad_total 41360
telemt_handshake_timeouts_total 12108
telemt_upstream_connect_attempt_total 10872
telemt_upstream_connect_success_total 10656
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 10872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4202
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_timeout_total 1877
telemt_me_reconnect_attempts_total 10145
telemt_me_reconnect_success_total 6726
telemt_me_reader_eof_total 7108
telemt_me_idle_close_by_peer_total 7107
telemt_me_route_drop_no_conn_total 200366
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 467959
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1580
telemt_desync_full_logged_total 422
telemt_desync_suppressed_total 1158
telemt_desync_frames_bucket_total{bucket="1_2"} 337
telemt_desync_frames_bucket_total{bucket="3_10"} 694
telemt_desync_frames_bucket_total{bucket="gt_10"} 549
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 6927
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 6718
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 469889
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 5036280037 (4.69 GB)
telemt_user_octets_to_client{user="hello"} 148857506488 (138.63 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 167799.6 (46h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3202527
telemt_connections_bad_total 29697
telemt_handshake_timeouts_total 214119
telemt_upstream_connect_attempt_total 37269
telemt_upstream_connect_success_total 37250
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 37269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17724
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 10196
telemt_me_reconnect_attempts_total 31140
telemt_me_reconnect_success_total 28568
telemt_me_reader_eof_total 30262
telemt_me_idle_close_by_peer_total 30261
telemt_me_route_drop_no_conn_total 1096950
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2653259
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8787
telemt_desync_full_logged_total 2927
telemt_desync_suppressed_total 5860
telemt_desync_frames_bucket_total{bucket="1_2"} 1451
telemt_desync_frames_bucket_total{bucket="3_10"} 3213
telemt_desync_frames_bucket_total{bucket="gt_10"} 4123
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 28914
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 28527
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 346
telemt_user_connections_total{user="hello"} 2652544
telemt_user_connections_current{user="hello"} 702
telemt_user_octets_from_client{user="hello"} 43715968748 (40.71 GB)
telemt_user_octets_to_client{user="hello"} 932911955493 (868.84 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 167800.2 (46h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2075867
telemt_connections_bad_total 22696
telemt_handshake_timeouts_total 195843
telemt_upstream_connect_attempt_total 52444
telemt_upstream_connect_success_total 50006
telemt_upstream_connect_fail_total 2301
telemt_upstream_connect_attempts_per_request{bucket="1"} 52170
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19757
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2300
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20205
telemt_me_reconnect_attempts_total 43629
telemt_me_reconnect_success_total 34618
telemt_me_reader_eof_total 37165
telemt_me_idle_close_by_peer_total 37158
telemt_me_route_drop_no_conn_total 733728
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1710685
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3685
telemt_desync_full_logged_total 1178
telemt_desync_suppressed_total 2507
telemt_desync_frames_bucket_total{bucket="1_2"} 972
telemt_desync_frames_bucket_total{bucket="3_10"} 1530
telemt_desync_frames_bucket_total{bucket="gt_10"} 1183
telemt_pool_swap_total 147
telemt_me_writer_removed_unexpected_total 35193
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 34594
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 575
telemt_user_connections_total{user="hello"} 1716554
telemt_user_connections_current{user="hello"} 431
telemt_user_octets_from_client{user="hello"} 26600240335 (24.77 GB)
telemt_user_octets_to_client{user="hello"} 643906653438 (599.68 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 37235.9 (10h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 577734
telemt_connections_bad_total 5763
telemt_handshake_timeouts_total 5511
telemt_upstream_connect_attempt_total 8279
telemt_upstream_connect_success_total 8011
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 8279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4168
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 968
telemt_me_reconnect_attempts_total 27990
telemt_me_reconnect_success_total 6123
telemt_me_reader_eof_total 6927
telemt_me_idle_close_by_peer_total 6926
telemt_me_route_drop_no_conn_total 219187
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 541993
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1479
telemt_desync_full_logged_total 458
telemt_desync_suppressed_total 1021
telemt_desync_frames_bucket_total{bucket="1_2"} 443
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 444
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6863
telemt_me_refill_failed_total 681
telemt_me_writer_restored_same_endpoint_total 6119
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 740
telemt_user_connections_total{user="hello"} 541938
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 6457151392 (6.01 GB)
telemt_user_octets_to_client{user="hello"} 172742193756 (160.88 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 61
```