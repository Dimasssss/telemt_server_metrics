# Server Metrics 2026-03-14 06:09:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 173441.1 (48h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4886137
telemt_connections_bad_total 40028
telemt_handshake_timeouts_total 112571
telemt_upstream_connect_attempt_total 36445
telemt_upstream_connect_success_total 36208
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 36445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_keepalive_timeout_total 7311
telemt_me_reconnect_attempts_total 35401
telemt_me_reconnect_success_total 25254
telemt_me_reader_eof_total 27104
telemt_me_idle_close_by_peer_total 27103
telemt_me_route_drop_no_conn_total 1851405
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4484194
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17236
telemt_desync_full_logged_total 4654
telemt_desync_suppressed_total 12582
telemt_desync_frames_bucket_total{bucket="1_2"} 4302
telemt_desync_frames_bucket_total{bucket="3_10"} 6583
telemt_desync_frames_bucket_total{bucket="gt_10"} 6351
telemt_pool_swap_total 152
telemt_me_writer_removed_unexpected_total 25933
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25241
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 679
telemt_user_connections_total{user="hello"} 4485720
telemt_user_connections_current{user="hello"} 1241
telemt_user_octets_from_client{user="hello"} 65501807356 (61.00 GB)
telemt_user_octets_to_client{user="hello"} 1414579673201 (1.29 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 375
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 73104.9 (20h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 796425
telemt_connections_bad_total 53421
telemt_handshake_timeouts_total 14627
telemt_upstream_connect_attempt_total 19916
telemt_upstream_connect_success_total 19646
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 19916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8565
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 2137
telemt_me_reconnect_attempts_total 17422
telemt_me_reconnect_success_total 13962
telemt_me_reader_eof_total 14845
telemt_me_idle_close_by_peer_total 14844
telemt_me_route_drop_no_conn_total 260123
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 630191
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1866
telemt_desync_full_logged_total 561
telemt_desync_suppressed_total 1305
telemt_desync_frames_bucket_total{bucket="1_2"} 386
telemt_desync_frames_bucket_total{bucket="3_10"} 838
telemt_desync_frames_bucket_total{bucket="gt_10"} 642
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 14265
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 13954
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 303
telemt_user_connections_total{user="hello"} 632143
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 6672428097 (6.21 GB)
telemt_user_octets_to_client{user="hello"} 212367837960 (197.78 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 203061.6 (56h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3510910
telemt_connections_bad_total 38549
telemt_handshake_timeouts_total 231474
telemt_upstream_connect_attempt_total 45933
telemt_upstream_connect_success_total 45912
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 45933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21453
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10651
telemt_me_reconnect_attempts_total 40476
telemt_me_reconnect_success_total 35503
telemt_me_reader_eof_total 37709
telemt_me_idle_close_by_peer_total 37708
telemt_me_route_drop_no_conn_total 1201046
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2927467
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9673
telemt_desync_full_logged_total 3247
telemt_desync_suppressed_total 6426
telemt_desync_frames_bucket_total{bucket="1_2"} 1691
telemt_desync_frames_bucket_total{bucket="3_10"} 3491
telemt_desync_frames_bucket_total{bucket="gt_10"} 4491
telemt_pool_swap_total 192
telemt_me_writer_removed_unexpected_total 35997
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 35462
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 494
telemt_user_connections_total{user="hello"} 2926630
telemt_user_connections_current{user="hello"} 722
telemt_user_octets_from_client{user="hello"} 48037756720 (44.74 GB)
telemt_user_octets_to_client{user="hello"} 1046988775117 (975.08 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 203064.1 (56h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2347435
telemt_connections_bad_total 23179
telemt_handshake_timeouts_total 272615
telemt_upstream_connect_attempt_total 63374
telemt_upstream_connect_success_total 60889
telemt_upstream_connect_fail_total 2348
telemt_upstream_connect_attempts_per_request{bucket="1"} 63100
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2347
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20498
telemt_me_reconnect_attempts_total 52813
telemt_me_reconnect_success_total 43770
telemt_me_reader_eof_total 46928
telemt_me_idle_close_by_peer_total 46921
telemt_me_route_drop_no_conn_total 793359
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1855963
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3889
telemt_desync_full_logged_total 1256
telemt_desync_suppressed_total 2633
telemt_desync_frames_bucket_total{bucket="1_2"} 1047
telemt_desync_frames_bucket_total{bucket="3_10"} 1616
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 180
telemt_me_writer_removed_unexpected_total 44430
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 43746
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 660
telemt_user_connections_total{user="hello"} 1861986
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 28152841759 (26.22 GB)
telemt_user_octets_to_client{user="hello"} 683915487810 (636.95 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 72497.7 (20h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 771330
telemt_connections_bad_total 8032
telemt_handshake_timeouts_total 9079
telemt_upstream_connect_attempt_total 18621
telemt_upstream_connect_success_total 18123
telemt_upstream_connect_fail_total 498
telemt_upstream_connect_attempts_per_request{bucket="1"} 18621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 498
telemt_me_keepalive_timeout_total 1570
telemt_me_reconnect_attempts_total 58434
telemt_me_reconnect_success_total 14505
telemt_me_reader_eof_total 16233
telemt_me_idle_close_by_peer_total 16232
telemt_me_route_drop_no_conn_total 296662
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 720461
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1761
telemt_desync_full_logged_total 563
telemt_desync_suppressed_total 1198
telemt_desync_frames_bucket_total{bucket="1_2"} 521
telemt_desync_frames_bucket_total{bucket="3_10"} 689
telemt_desync_frames_bucket_total{bucket="gt_10"} 551
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 16003
telemt_me_refill_failed_total 1368
telemt_me_writer_restored_same_endpoint_total 14500
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1498
telemt_user_connections_total{user="hello"} 720315
telemt_user_connections_current{user="hello"} 517
telemt_user_octets_from_client{user="hello"} 12827775184 (11.95 GB)
telemt_user_octets_to_client{user="hello"} 241113336632 (224.55 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 75
```