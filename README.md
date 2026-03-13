# Server Metrics 2026-03-13 20:47:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 139707.0 (38h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4430882
telemt_connections_bad_total 37961
telemt_handshake_timeouts_total 106192
telemt_upstream_connect_attempt_total 29209
telemt_upstream_connect_success_total 29010
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 29209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12901
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_timeout_total 6557
telemt_me_reconnect_attempts_total 29808
telemt_me_reconnect_success_total 19690
telemt_me_reader_eof_total 21134
telemt_me_idle_close_by_peer_total 21133
telemt_me_route_drop_no_conn_total 1669135
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4057048
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16150
telemt_desync_full_logged_total 4305
telemt_desync_suppressed_total 11845
telemt_desync_frames_bucket_total{bucket="1_2"} 4031
telemt_desync_frames_bucket_total{bucket="3_10"} 6158
telemt_desync_frames_bucket_total{bucket="gt_10"} 5961
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 20288
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19677
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 598
telemt_user_connections_total{user="hello"} 4059184
telemt_user_connections_current{user="hello"} 1195
telemt_user_octets_from_client{user="hello"} 59878660900 (55.77 GB)
telemt_user_octets_to_client{user="hello"} 1282743052581 (1.17 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 39370.8 (10h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 553166
telemt_connections_bad_total 41399
telemt_handshake_timeouts_total 12167
telemt_upstream_connect_attempt_total 11302
telemt_upstream_connect_success_total 11084
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 11302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4391
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 1886
telemt_me_reconnect_attempts_total 10502
telemt_me_reconnect_success_total 7080
telemt_me_reader_eof_total 7480
telemt_me_idle_close_by_peer_total 7479
telemt_me_route_drop_no_conn_total 204287
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 480019
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1622
telemt_desync_full_logged_total 437
telemt_desync_suppressed_total 1185
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 707
telemt_desync_frames_bucket_total{bucket="gt_10"} 571
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 7289
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 7072
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 481948
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 5181183117 (4.83 GB)
telemt_user_octets_to_client{user="hello"} 152421600320 (141.95 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 169327.7 (47h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3224615
telemt_connections_bad_total 30070
telemt_handshake_timeouts_total 214880
telemt_upstream_connect_attempt_total 37698
telemt_upstream_connect_success_total 37678
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 37698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17858
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 10224
telemt_me_reconnect_attempts_total 32763
telemt_me_reconnect_success_total 28908
telemt_me_reader_eof_total 30641
telemt_me_idle_close_by_peer_total 30640
telemt_me_route_drop_no_conn_total 1105111
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2673826
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8838
telemt_desync_full_logged_total 2964
telemt_desync_suppressed_total 5874
telemt_desync_frames_bucket_total{bucket="1_2"} 1462
telemt_desync_frames_bucket_total{bucket="3_10"} 3226
telemt_desync_frames_bucket_total{bucket="gt_10"} 4150
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 29298
telemt_me_refill_failed_total 115
telemt_me_writer_restored_same_endpoint_total 28867
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 390
telemt_user_connections_total{user="hello"} 2673107
telemt_user_connections_current{user="hello"} 633
telemt_user_octets_from_client{user="hello"} 44000371496 (40.98 GB)
telemt_user_octets_to_client{user="hello"} 941166297433 (876.53 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 169327.9 (47h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2092878
telemt_connections_bad_total 22776
telemt_handshake_timeouts_total 199958
telemt_upstream_connect_attempt_total 52744
telemt_upstream_connect_success_total 50304
telemt_upstream_connect_fail_total 2303
telemt_upstream_connect_attempts_per_request{bucket="1"} 52470
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2302
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20219
telemt_me_reconnect_attempts_total 43841
telemt_me_reconnect_success_total 34830
telemt_me_reader_eof_total 37389
telemt_me_idle_close_by_peer_total 37382
telemt_me_route_drop_no_conn_total 739019
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1723328
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3696
telemt_desync_full_logged_total 1184
telemt_desync_suppressed_total 2512
telemt_desync_frames_bucket_total{bucket="1_2"} 980
telemt_desync_frames_bucket_total{bucket="3_10"} 1533
telemt_desync_frames_bucket_total{bucket="gt_10"} 1183
telemt_pool_swap_total 149
telemt_me_writer_removed_unexpected_total 35409
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 34806
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 579
telemt_user_connections_total{user="hello"} 1729199
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 26848353731 (25.00 GB)
telemt_user_octets_to_client{user="hello"} 646923732542 (602.49 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 38763.4 (10h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 590953
telemt_connections_bad_total 5788
telemt_handshake_timeouts_total 5565
telemt_upstream_connect_attempt_total 8549
telemt_upstream_connect_success_total 8273
telemt_upstream_connect_fail_total 276
telemt_upstream_connect_attempts_per_request{bucket="1"} 8549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 276
telemt_me_keepalive_timeout_total 969
telemt_me_reconnect_attempts_total 29571
telemt_me_reconnect_success_total 6327
telemt_me_reader_eof_total 7174
telemt_me_idle_close_by_peer_total 7173
telemt_me_route_drop_no_conn_total 223909
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 554770
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1482
telemt_desync_full_logged_total 459
telemt_desync_suppressed_total 1023
telemt_desync_frames_bucket_total{bucket="1_2"} 445
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 445
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 7110
telemt_me_refill_failed_total 724
telemt_me_writer_restored_same_endpoint_total 6323
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 783
telemt_user_connections_total{user="hello"} 554702
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 8287252308 (7.72 GB)
telemt_user_octets_to_client{user="hello"} 176357814580 (164.25 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 59
```